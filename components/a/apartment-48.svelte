<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-0gtbbyk.css';
import '../../css/n/nvnghdcdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y-0gtbbyk"/><path class="nvnghdcdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apartment-48" {...props}></Icon>
