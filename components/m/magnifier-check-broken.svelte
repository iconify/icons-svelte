<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o3o_tvbax.css';
import '../../css/x/x09loybdy.css';
import '../../css/f/fzogdacmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o3o_tvbax"/><path class="x09loybdy"/><path class="fzogdacmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-check-broken" {...props}></Icon>
