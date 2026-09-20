<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fys9o6byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fys9o6byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:error" {...props}></Icon>
