<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh5fs6bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh5fs6bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-check-fill" {...props}></Icon>
