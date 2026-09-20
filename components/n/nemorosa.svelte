<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chs0ajpjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="chs0ajpjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nemorosa" {...props}></Icon>
