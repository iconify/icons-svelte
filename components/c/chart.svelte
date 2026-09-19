<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcx2xzbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="mcx2xzbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:chart" {...props}></Icon>
