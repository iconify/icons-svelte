<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5uwqqndl.css';
import '../../css/a/a318uacfc.css';
import '../../css/u/ujn-tbcgw.css';
import '../../css/q/qcdgrwbvv.css';
import '../../css/n/nkzil-o-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o5uwqqndl"/><path class="a318uacfc"/><path class="ujn-tbcgw"/><path class="qcdgrwbvv"/><path class="nkzil-o-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-ship-20-bold" {...props}></Icon>
