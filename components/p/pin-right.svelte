<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkraz_b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hkraz_b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:pin-right" {...props}></Icon>
