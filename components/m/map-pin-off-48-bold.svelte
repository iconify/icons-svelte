<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keo7l-5me.css';
import '../../css/a/ad8--_xso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="keo7l-5me"/><path class="ad8--_xso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-off-48-bold" {...props}></Icon>
