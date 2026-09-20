<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaum-2bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aaum-2bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-desktop-16" {...props}></Icon>
