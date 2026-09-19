<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leig0z_lw.css';
import '../../css/u/uitb-4b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leig0z_lw"/><path class="uitb-4b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:mcp" {...props}></Icon>
