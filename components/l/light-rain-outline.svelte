<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwdc88brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dwdc88brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:light-rain-outline" {...props}></Icon>
