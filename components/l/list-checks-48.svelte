<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp-dk2bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rp-dk2bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-checks-48" {...props}></Icon>
