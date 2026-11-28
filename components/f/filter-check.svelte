<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqozz7blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqozz7blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:filter-check" {...props}></Icon>
