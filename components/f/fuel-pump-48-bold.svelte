<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec_hp_w4i.css';
import '../../css/o/ort250bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ec_hp_w4i"/><path class="ort250bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-pump-48-bold" {...props}></Icon>
