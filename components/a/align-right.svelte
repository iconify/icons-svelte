<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt7x1qbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mt7x1qbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:align-right" {...props}></Icon>
