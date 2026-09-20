<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uvbc2lbfi.css';
import '../../css/o/ohys8lu6y.css';
import '../../css/j/j6ohuicfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uvbc2lbfi"/><path class="ohys8lu6y"/><path class="j6ohuicfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-right-broken" {...props}></Icon>
