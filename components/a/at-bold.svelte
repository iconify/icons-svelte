<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmh3annxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xmh3annxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:at-bold" {...props}></Icon>
