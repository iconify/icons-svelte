<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d__-w4beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d__-w4beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:health-filled" {...props}></Icon>
