<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb_r3_53g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yb_r3_53g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:angrycreative" {...props}></Icon>
