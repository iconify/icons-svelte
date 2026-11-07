<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/un29iqbuk.css';
import '../../css/f/fuprorb1g.css';
import '../../css/r/r5lvzac_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="un29iqbuk"/><path class="fuprorb1g"/><path class="r5lvzac_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-lock-linear" {...props}></Icon>
