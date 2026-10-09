<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvvq2qbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gvvq2qbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:code-2-48-bold" {...props}></Icon>
