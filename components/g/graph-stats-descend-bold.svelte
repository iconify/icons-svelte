<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn279sbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn279sbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:graph-stats-descend-bold" {...props}></Icon>
