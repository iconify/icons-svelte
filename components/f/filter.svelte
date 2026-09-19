<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imx_s_bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="imx_s_bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:filter" {...props}></Icon>
