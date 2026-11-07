<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i1vfzkb9v.css';
import '../../css/e/ehgxs22fz.css';
import '../../css/c/ctgpv1blf.css';
import '../../css/w/w9x56_fne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i1vfzkb9v"/><path class="ehgxs22fz"/><path class="ctgpv1blf"/><path class="w9x56_fne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:palette-linear" {...props}></Icon>
