<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhvj11uls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rhvj11uls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:controls-play" {...props}></Icon>
