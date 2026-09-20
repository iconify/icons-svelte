<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_1_ixbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g_1_ixbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:check-stand-outline" {...props}></Icon>
