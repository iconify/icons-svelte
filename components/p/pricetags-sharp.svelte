<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udf6_wwmv.css';
import '../../css/l/lizw1zvth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udf6_wwmv"/><path class="lizw1zvth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pricetags-sharp" {...props}></Icon>
