<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kny6_hb4a.css';
import '../../css/r/rys9nkbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kny6_hb4a"/><path class="rys9nkbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-family" {...props}></Icon>
