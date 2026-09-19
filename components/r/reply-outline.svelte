<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd7edwb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cd7edwb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:reply-outline" {...props}></Icon>
