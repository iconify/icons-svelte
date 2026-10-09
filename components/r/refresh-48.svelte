<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz1-3kbvd.css';
import '../../css/k/kpheslb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yz1-3kbvd"/><path class="kpheslb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-48" {...props}></Icon>
