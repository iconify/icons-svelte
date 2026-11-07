<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt6umrt6x.css';
import '../../css/p/p60zoqpev.css';
import '../../css/m/ma9vvmbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt6umrt6x"/><path class="p60zoqpev"/><path clip-rule="evenodd" class="ma9vvmbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-5-outline" {...props}></Icon>
