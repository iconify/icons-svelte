<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6dfp0bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6dfp0bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:perspective-off" {...props}></Icon>
