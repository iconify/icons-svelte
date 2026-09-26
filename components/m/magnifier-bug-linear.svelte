<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hllyxzboc.css';
import '../../css/i/ig7l8tpsj.css';
import '../../css/o/o3o_tvbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="hllyxzboc"/><path class="ig7l8tpsj"/><path class="o3o_tvbax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-bug-linear" {...props}></Icon>
