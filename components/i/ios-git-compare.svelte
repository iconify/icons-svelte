<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ansskgocr.css';
import '../../css/f/f_g898bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ansskgocr"/><path class="f_g898bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-git-compare" {...props}></Icon>
