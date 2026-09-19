<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8lam-buj.css';
import '../../css/c/cyt_a1kut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="s8lam-buj"/><path class="cyt_a1kut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:regular-shape-pt" {...props}></Icon>
