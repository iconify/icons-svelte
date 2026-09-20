<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm_2psbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cm_2psbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:japanese-teacup" {...props}></Icon>
