<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9xxpvb-v.css';
import '../../css/e/e2fb1bb0n.css';
import '../../css/o/o24sug9tq.css';
import '../../css/b/b1dg_9oeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t9xxpvb-v"/><path class="e2fb1bb0n"/><path class="o24sug9tq"/><path class="b1dg_9oeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-off-20" {...props}></Icon>
