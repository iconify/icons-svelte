<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp5e80bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="zp5e80bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid" {...props}></Icon>
