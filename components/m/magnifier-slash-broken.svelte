<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o3o_tvbax.css';
import '../../css/x/x09loybdy.css';
import '../../css/y/y6zoopbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o3o_tvbax"/><path class="x09loybdy"/><path class="y6zoopbyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-slash-broken" {...props}></Icon>
