<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5sf_o82m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w5sf_o82m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-frown-open" {...props}></Icon>
