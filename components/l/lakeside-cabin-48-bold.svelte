<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_ts8_bno.css';
import '../../css/m/mmtwl7b9d.css';
import '../../css/b/bpxnjdbqd.css';
import '../../css/f/fpzuy5-2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r_ts8_bno"/><path class="mmtwl7b9d"/><path class="bpxnjdbqd"/><path class="fpzuy5-2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lakeside-cabin-48-bold" {...props}></Icon>
