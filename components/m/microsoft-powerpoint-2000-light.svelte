<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptqwy9b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptqwy9b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powerpoint-2000-light" {...props}></Icon>
