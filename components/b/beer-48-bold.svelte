<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2p4lbbrb.css';
import '../../css/q/q0z4gbkbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z2p4lbbrb"/><path class="q0z4gbkbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:beer-48-bold" {...props}></Icon>
