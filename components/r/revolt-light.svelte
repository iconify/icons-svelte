<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wes_5_bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wes_5_bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:revolt-light" {...props}></Icon>
