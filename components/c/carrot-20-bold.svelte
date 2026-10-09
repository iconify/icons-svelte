<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l361dvbca.css';
import '../../css/h/hud-elbct.css';
import '../../css/a/ahkc9jbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l361dvbca"/><path class="hud-elbct"/><path class="ahkc9jbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carrot-20-bold" {...props}></Icon>
