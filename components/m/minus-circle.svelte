<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iks3biblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iks3biblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:minus-circle" {...props}></Icon>
