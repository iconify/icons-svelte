<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bnn6dbcbc.css';
import '../../css/m/m6hvbi_wp.css';
import '../../css/p/pq26m6iud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bnn6dbcbc"/><path class="m6hvbi_wp"/><path class="pq26m6iud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-close-linear" {...props}></Icon>
