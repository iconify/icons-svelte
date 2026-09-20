<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/whspc0b_i.css';
import '../../css/f/f67y05bux.css';
import '../../css/n/n7itbbc5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="whspc0b_i"/><path class="f67y05bux"/><path class="n7itbbc5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kanban-linear" {...props}></Icon>
