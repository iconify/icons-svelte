<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki9lj6b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki9lj6b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-treemap-round" {...props}></Icon>
