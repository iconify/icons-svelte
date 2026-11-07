<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p9h4jybmo.css';
import '../../css/f/fdi87hbgw.css';
import '../../css/u/urwe8bb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p9h4jybmo"/><path class="fdi87hbgw"/><path class="urwe8bb9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:close-broken" {...props}></Icon>
