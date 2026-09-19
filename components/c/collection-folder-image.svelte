<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4ecrjb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":432};
const content = `<path class="j4ecrjb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-folder-image" {...props}></Icon>
