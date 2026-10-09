<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_kcw3bme.css';
import '../../css/z/zryj4abdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l_kcw3bme"/><path class="zryj4abdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-48" {...props}></Icon>
