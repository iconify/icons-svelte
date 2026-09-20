<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luhxm1b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="luhxm1b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-full-1" {...props}></Icon>
