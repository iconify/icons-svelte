<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-ojc6gmg.css';
import '../../css/l/ldfs6kdmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-ojc6gmg"/><path class="ldfs6kdmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:reddit" {...props}></Icon>
