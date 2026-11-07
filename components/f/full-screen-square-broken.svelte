<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nerijcc5y.css';
import '../../css/f/fsxwe0nbu.css';
import '../../css/g/girv7pn6s.css';
import '../../css/n/n-dhbzbjq.css';
import '../../css/s/si_mtzbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nerijcc5y"/><path class="fsxwe0nbu"/><path class="girv7pn6s"/><path class="n-dhbzbjq"/><path class="si_mtzbvj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-square-broken" {...props}></Icon>
