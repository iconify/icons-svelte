<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7i9-fbzj.css';
import '../../css/k/k6t8-bcyt.css';
import '../../css/i/i6pxhx3fr.css';
import '../../css/v/venxv696d.css';
import '../../css/h/h4nmdubtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d7i9-fbzj"/><path class="k6t8-bcyt"/><path class="i6pxhx3fr"/><path class="venxv696d"/><path class="h4nmdubtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-ship-48-bold" {...props}></Icon>
