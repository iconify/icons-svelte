<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vgbcb_s.css';
import '../../css/x/xhmpe1o6k.css';
import '../../css/s/soapwv82a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="xhmpe1o6k"/><path class="soapwv82a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:gb-eng-4x3" {...props}></Icon>
