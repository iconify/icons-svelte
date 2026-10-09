<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okbu3-k6y.css';
import '../../css/p/pzfwzzb9e.css';
import '../../css/b/bhjkzgb5r.css';
import '../../css/f/fm6x645ov.css';
import '../../css/r/rtl-k8b6b.css';
import '../../css/o/om-j69jmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="okbu3-k6y"/><path class="pzfwzzb9e"/><path class="bhjkzgb5r"/><path class="fm6x645ov"/><path class="rtl-k8b6b"/><path class="om-j69jmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:agrivoltaics-20" {...props}></Icon>
