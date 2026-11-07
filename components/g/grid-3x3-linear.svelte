<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e0c96qb6a.css';
import '../../css/v/vddq6r-de.css';
import '../../css/f/faouxb3ly.css';
import '../../css/t/ts3tpkwrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0c96qb6a"/><path class="vddq6r-de"/><path class="faouxb3ly"/><path class="ts3tpkwrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-3x3-linear" {...props}></Icon>
