<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj1oo60oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kj1oo60oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:element-light" {...props}></Icon>
