<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnhy8pd4d.css';
import '../../css/s/srze-hcsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nnhy8pd4d"/><path class="srze-hcsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-chatbubbles" {...props}></Icon>
