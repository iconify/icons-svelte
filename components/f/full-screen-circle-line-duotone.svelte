<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nerijcc5y.css';
import '../../css/g/gqca22zsx.css';
import '../../css/f/f69dim7yf.css';
import '../../css/k/k1rt0cbye.css';
import '../../css/d/doy9q4b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nerijcc5y"/><path class="gqca22zsx"/><path class="f69dim7yf"/><path class="k1rt0cbye"/><circle class="doy9q4b5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-circle-line-duotone" {...props}></Icon>
