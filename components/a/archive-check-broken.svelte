<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/q4xke4y0d.css';
import '../../css/m/m97iezbay.css';
import '../../css/m/mjojrgq4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q4xke4y0d"/><path class="m97iezbay"/><path class="mjojrgq4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-check-broken" {...props}></Icon>
