<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puno4n5gf.css';
import '../../css/u/ufakx9rlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":511.875,"height":511.824};
const content = `<path class="puno4n5gf"/><path class="ufakx9rlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:racket" {...props}></Icon>
