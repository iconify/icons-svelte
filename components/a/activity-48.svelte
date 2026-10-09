<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk1kbxbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dk1kbxbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:activity-48" {...props}></Icon>
