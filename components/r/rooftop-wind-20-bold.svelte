<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3lgxlbxk.css';
import '../../css/s/shu9gmbgv.css';
import '../../css/n/nbpoujbxo.css';
import '../../css/v/vsoe54eox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j3lgxlbxk"/><path class="shu9gmbgv"/><path class="nbpoujbxo"/><path class="vsoe54eox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rooftop-wind-20-bold" {...props}></Icon>
