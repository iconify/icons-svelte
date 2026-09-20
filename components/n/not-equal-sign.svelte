<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiph_s-7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="eiph_s-7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:not-equal-sign" {...props}></Icon>
