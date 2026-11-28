<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww1sdi6gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww1sdi6gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:car" {...props}></Icon>
