<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4_s0eafu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m4_s0eafu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:exclamation-mark" {...props}></Icon>
