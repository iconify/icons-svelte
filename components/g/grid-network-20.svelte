<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg1we5wmy.css';
import '../../css/w/wz_jv-b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tg1we5wmy"/><path class="wz_jv-b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-network-20" {...props}></Icon>
