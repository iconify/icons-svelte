<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1hov4txr.css';
import '../../css/o/o_hufdbvo.css';
import '../../css/u/ujk3pta6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m1hov4txr"/><path class="o_hufdbvo"/><path class="ujk3pta6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-dropper-20-bold" {...props}></Icon>
