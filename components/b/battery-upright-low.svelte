<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx98c1b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rx98c1b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-upright-low" {...props}></Icon>
