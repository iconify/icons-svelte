<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v75o0q40y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v75o0q40y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openwrt-dark" {...props}></Icon>
