<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9itrbcfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y9itrbcfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-48" {...props}></Icon>
