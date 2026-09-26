<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r0xhknb7f.css';
import '../../css/o/o3o_tvbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="r0xhknb7f"/><path class="o3o_tvbax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-line-duotone" {...props}></Icon>
