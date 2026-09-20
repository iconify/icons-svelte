<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh7uwob5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fh7uwob5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-xmark" {...props}></Icon>
