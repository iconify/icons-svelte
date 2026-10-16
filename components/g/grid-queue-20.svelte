<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_f_kcb1a.css';
import '../../css/j/js7r36bge.css';
import '../../css/p/pjegvpb6r.css';
import '../../css/r/rbi3a9cbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w_f_kcb1a"/><path class="js7r36bge"/><path class="pjegvpb6r"/><path class="rbi3a9cbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-queue-20" {...props}></Icon>
