<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkl3kalhn.css';
import '../../css/x/xkgq43b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dkl3kalhn"/><path class="xkgq43b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bold-48" {...props}></Icon>
