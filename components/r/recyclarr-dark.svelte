<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgbkh123w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xgbkh123w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:recyclarr-dark" {...props}></Icon>
