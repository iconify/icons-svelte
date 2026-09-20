<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1nu-xiim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":208};
const content = `<path class="u1nu-xiim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:github-copilot-light" {...props}></Icon>
