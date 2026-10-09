<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb962gbar.css';
import '../../css/u/ukm6slb5o.css';
import '../../css/j/j15ob97qd.css';
import '../../css/g/g6t4fyb_i.css';
import '../../css/x/xnd446bty.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rb962gbar"/><path class="ukm6slb5o"/><path class="j15ob97qd"/><path class="g6t4fyb_i"/><path class="xnd446bty"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:balcony-solar-20-bold" {...props}></Icon>
