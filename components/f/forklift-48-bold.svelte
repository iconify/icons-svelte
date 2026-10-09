<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctpcvf1md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ctpcvf1md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forklift-48-bold" {...props}></Icon>
