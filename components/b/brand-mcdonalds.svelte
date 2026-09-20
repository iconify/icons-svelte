<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfuenvb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfuenvb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-mcdonalds" {...props}></Icon>
