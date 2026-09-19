<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we9xjz3rp.css';
import '../../css/g/g2vc8actl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="we9xjz3rp"/><path class="g2vc8actl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-images" {...props}></Icon>
