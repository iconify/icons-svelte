<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfgpndd3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cfgpndd3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:hash" {...props}></Icon>
