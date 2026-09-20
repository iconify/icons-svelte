<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2yj4pmym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t2yj4pmym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:inquiry-filled" {...props}></Icon>
