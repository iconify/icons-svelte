<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsdbu57tf.css';
import '../../css/r/rz0vntz2v.css';
import '../../css/s/soc2sjb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsdbu57tf"/><path class="rz0vntz2v"/><path class="soc2sjb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kamiyomu" {...props}></Icon>
