<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffan0e92o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ffan0e92o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:quarry-48-bold" {...props}></Icon>
