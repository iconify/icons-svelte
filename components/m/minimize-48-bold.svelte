<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7sy_0byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v7sy_0byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minimize-48-bold" {...props}></Icon>
