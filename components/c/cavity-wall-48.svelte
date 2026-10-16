<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifyp2_bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ifyp2_bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cavity-wall-48" {...props}></Icon>
