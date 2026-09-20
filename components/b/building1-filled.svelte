<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vti7wdbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vti7wdbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:building1-filled" {...props}></Icon>
