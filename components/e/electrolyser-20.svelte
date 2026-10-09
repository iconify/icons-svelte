<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cozw5lxrq.css';
import '../../css/w/wkvt3obva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cozw5lxrq"/><path class="wkvt3obva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electrolyser-20" {...props}></Icon>
