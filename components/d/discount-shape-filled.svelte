<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwmxdo9_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwmxdo9_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:discount-shape-filled" {...props}></Icon>
