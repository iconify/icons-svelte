<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6_diewni.css';
import '../../css/s/s2uksm1sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c6_diewni"/><path class="s2uksm1sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pen-sparkle-48-bold" {...props}></Icon>
