<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7474gbcq.css';
import '../../css/w/w2h_ynbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w7474gbcq"/><path class="w2h_ynbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:baby-48" {...props}></Icon>
