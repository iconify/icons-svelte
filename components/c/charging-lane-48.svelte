<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxy5bwbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hxy5bwbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-lane-48" {...props}></Icon>
