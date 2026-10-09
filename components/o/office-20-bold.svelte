<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_1_eqb9t.css';
import '../../css/q/q02p0rb4d.css';
import '../../css/f/fwy8obcmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n_1_eqb9t"/><path class="q02p0rb4d"/><path class="fwy8obcmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:office-20-bold" {...props}></Icon>
