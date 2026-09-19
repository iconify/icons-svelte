<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9lp8vb8r.css';
import '../../css/g/gezdqco1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9lp8vb8r"/><path class="gezdqco1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pricetags-outline" {...props}></Icon>
