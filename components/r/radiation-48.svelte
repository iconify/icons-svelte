<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr4v5jaad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xr4v5jaad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiation-48" {...props}></Icon>
