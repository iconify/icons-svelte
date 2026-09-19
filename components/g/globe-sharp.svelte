<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfb5d6b_i.css';
import '../../css/b/bt4w0gb_w.css';
import '../../css/g/g40sm1q7e.css';
import '../../css/y/yf66grb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfb5d6b_i"/><path class="bt4w0gb_w"/><path class="g40sm1q7e"/><path class="yf66grb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:globe-sharp" {...props}></Icon>
