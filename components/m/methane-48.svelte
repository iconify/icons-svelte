<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbi25pb1n.css';
import '../../css/i/ijb4gt58w.css';
import '../../css/v/vbh2_55tf.css';
import '../../css/n/nt-jk7fef.css';
import '../../css/n/n6d0kus7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wbi25pb1n"/><path class="ijb4gt58w"/><path class="vbh2_55tf"/><path class="nt-jk7fef"/><path class="n6d0kus7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:methane-48" {...props}></Icon>
