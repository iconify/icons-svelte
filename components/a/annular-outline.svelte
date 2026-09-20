<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svpwfgbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="svpwfgbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:annular-outline" {...props}></Icon>
