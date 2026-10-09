<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we15u_h7x.css';
import '../../css/q/qg66_ubxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="we15u_h7x"/><path class="qg66_ubxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-open-48" {...props}></Icon>
