<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc-4xxsbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="lc-4xxsbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:devices" {...props}></Icon>
