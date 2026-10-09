<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fad7f9tkf.css';
import '../../css/n/nq0-d_lbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fad7f9tkf"/><path class="nq0-d_lbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grass-20-bold" {...props}></Icon>
