<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtemedn_h.css';
import '../../css/y/y1jnin_gq.css';
import '../../css/r/rl-2a6bga.css';
import '../../css/s/srqm21bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rtemedn_h"/><path class="y1jnin_gq"/><path class="rl-2a6bga"/><path class="srqm21bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-cycle-48-bold" {...props}></Icon>
