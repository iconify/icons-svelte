<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr_8bt_rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sr_8bt_rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bookmark" {...props}></Icon>
