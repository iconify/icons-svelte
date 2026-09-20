<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brxsehb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brxsehb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-add-outline" {...props}></Icon>
