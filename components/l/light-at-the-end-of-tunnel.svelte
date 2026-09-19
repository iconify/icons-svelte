<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0p-a1baf.css';
import '../../css/u/uu8vm-ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u0p-a1baf"/><path class="uu8vm-ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:light-at-the-end-of-tunnel" {...props}></Icon>
