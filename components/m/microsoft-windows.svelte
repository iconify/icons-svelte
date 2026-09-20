<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s62818bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s62818bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-windows" {...props}></Icon>
