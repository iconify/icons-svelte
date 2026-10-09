<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyg_4gbyx.css';
import '../../css/x/xua85z4wn.css';
import '../../css/p/petbblbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nyg_4gbyx"/><path class="xua85z4wn"/><path class="petbblbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-48" {...props}></Icon>
