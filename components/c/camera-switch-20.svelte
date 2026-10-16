<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umcbrdrzf.css';
import '../../css/n/nwmd57bti.css';
import '../../css/t/thdncb4gb.css';
import '../../css/i/i8kflg27r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="umcbrdrzf"/><path class="nwmd57bti"/><path class="thdncb4gb"/><path class="i8kflg27r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-switch-20" {...props}></Icon>
