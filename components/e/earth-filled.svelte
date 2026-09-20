<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t85489bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t85489bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:earth-filled" {...props}></Icon>
