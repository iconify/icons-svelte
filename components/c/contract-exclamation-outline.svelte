<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgo_ukb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dgo_ukb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:contract-exclamation-outline" {...props}></Icon>
