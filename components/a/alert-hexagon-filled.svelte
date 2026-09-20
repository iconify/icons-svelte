<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azqc4mbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azqc4mbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-hexagon-filled" {...props}></Icon>
