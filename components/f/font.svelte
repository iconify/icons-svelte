<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl8_8wpxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="nl8_8wpxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:font" {...props}></Icon>
