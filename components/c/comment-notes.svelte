<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w53kg79zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w53kg79zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-notes" {...props}></Icon>
