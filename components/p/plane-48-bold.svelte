<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz4--lb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nz4--lb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plane-48-bold" {...props}></Icon>
