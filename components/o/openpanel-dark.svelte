<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3xgmdvlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r3xgmdvlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openpanel-dark" {...props}></Icon>
