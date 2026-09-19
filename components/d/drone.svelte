<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aro0gib6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aro0gib6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:drone" {...props}></Icon>
