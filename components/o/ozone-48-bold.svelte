<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmfh5sz3m.css';
import '../../css/l/llzzeg-xn.css';
import '../../css/i/ixr-80b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmfh5sz3m"/><path class="llzzeg-xn"/><path class="ixr-80b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ozone-48-bold" {...props}></Icon>
