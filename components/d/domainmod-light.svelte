<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loycbjbia.css';
import '../../css/w/w3qyplb8m.css';
import '../../css/i/ihoo6dbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="loycbjbia"/><path class="w3qyplb8m"/><path class="ihoo6dbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domainmod-light" {...props}></Icon>
