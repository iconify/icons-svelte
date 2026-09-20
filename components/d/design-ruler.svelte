<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw-zbzb4r.css';
import '../../css/x/xc1w02vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gw-zbzb4r"/><path class="xc1w02vnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-ruler" {...props}></Icon>
