<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db6myboly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db6myboly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-rhombus" {...props}></Icon>
