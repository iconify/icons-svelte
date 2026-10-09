<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr3nhqbhi.css';
import '../../css/h/hf81d2y0d.css';
import '../../css/q/qkpwe6b5c.css';
import '../../css/g/g0ni6vb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xr3nhqbhi"/><path class="hf81d2y0d"/><path class="qkpwe6b5c"/><path class="g0ni6vb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forest-20" {...props}></Icon>
