<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgrpurb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xgrpurb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-frown" {...props}></Icon>
