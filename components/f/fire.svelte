<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtshw__nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dtshw__nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:fire" {...props}></Icon>
