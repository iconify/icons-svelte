<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv-rcc7eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="kv-rcc7eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:forecast-io-rain" {...props}></Icon>
