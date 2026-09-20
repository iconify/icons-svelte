<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9xycefpv.css';
import '../../css/w/w9ster-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9xycefpv"/><path class="w9ster-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-bing-bold-duotone" {...props}></Icon>
