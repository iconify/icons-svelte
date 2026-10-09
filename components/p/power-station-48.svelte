<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1j5nsboq.css';
import '../../css/p/pwrb__blp.css';
import '../../css/q/qrfic8bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j1j5nsboq"/><path class="pwrb__blp"/><path class="qrfic8bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-48" {...props}></Icon>
