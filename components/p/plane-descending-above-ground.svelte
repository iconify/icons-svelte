<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqzszg6lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qqzszg6lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-descending-above-ground" {...props}></Icon>
