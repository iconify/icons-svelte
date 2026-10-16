<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-flw2bql.css';
import '../../css/v/vbmukxb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m-flw2bql"/><path class="vbmukxb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pc-tower-48" {...props}></Icon>
