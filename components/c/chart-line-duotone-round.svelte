<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cftlv9b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cftlv9b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-line-duotone-round" {...props}></Icon>
