<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zziiasbpq.css';
import '../../css/z/z176l2i0d.css';
import '../../css/u/ubkr3mbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":720,"height":720};
const content = `<path class="zziiasbpq"/><path class="z176l2i0d"/><path class="ubkr3mbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:matlab" {...props}></Icon>
