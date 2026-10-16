<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uobcpjbvq.css';
import '../../css/r/rogied72y.css';
import '../../css/t/tpcfugidh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uobcpjbvq"/><path class="rogied72y"/><path class="tpcfugidh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-output-48" {...props}></Icon>
