<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3hqt2bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d3hqt2bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crowbar-48" {...props}></Icon>
