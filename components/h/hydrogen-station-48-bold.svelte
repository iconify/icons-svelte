<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec_hp_w4i.css';
import '../../css/m/mh6unsbvq.css';
import '../../css/q/qk2_ljb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ec_hp_w4i"/><path class="mh6unsbvq"/><path class="qk2_ljb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-station-48-bold" {...props}></Icon>
