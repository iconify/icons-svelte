<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k7mximbwp.css';
import '../../css/d/dehy6rvzp.css';
import '../../css/k/k70ayubab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k7mximbwp"/><path class="dehy6rvzp"/><path class="k70ayubab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-square-line-duotone" {...props}></Icon>
