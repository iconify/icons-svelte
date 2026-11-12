<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p12ryjbsv.css';
import '../../css/k/k5azw7b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p12ryjbsv"/><path class="k5azw7b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:revel" {...props}></Icon>
