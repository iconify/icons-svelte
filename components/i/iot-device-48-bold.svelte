<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gphkpac7l.css';
import '../../css/c/cwzf0sb5m.css';
import '../../css/p/poayr0wpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gphkpac7l"/><path class="cwzf0sb5m"/><path class="poayr0wpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:iot-device-48-bold" {...props}></Icon>
