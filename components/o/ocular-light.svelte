<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n49rf8_vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n49rf8_vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ocular-light" {...props}></Icon>
