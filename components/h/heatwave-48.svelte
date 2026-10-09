<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxju_n3um.css';
import '../../css/f/fow8b5buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nxju_n3um"/><path class="fow8b5buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heatwave-48" {...props}></Icon>
