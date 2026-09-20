<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xih3-epmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xih3-epmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:five-plus-above-water" {...props}></Icon>
