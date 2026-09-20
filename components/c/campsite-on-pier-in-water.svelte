<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo1qmrsci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bo1qmrsci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-on-pier-in-water" {...props}></Icon>
