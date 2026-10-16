<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcwf1bbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vcwf1bbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ocean-acidification-48-bold" {...props}></Icon>
