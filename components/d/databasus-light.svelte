<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uon3nobpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uon3nobpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:databasus-light" {...props}></Icon>
