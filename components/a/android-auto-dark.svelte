<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5e_cby5o.css';
import '../../css/t/tncgtrlau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5e_cby5o"/><path class="tncgtrlau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-auto-dark" {...props}></Icon>
