<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdk2_smhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pdk2_smhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-center-horizontal-outline" {...props}></Icon>
