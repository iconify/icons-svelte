<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1z0783yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1z0783yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-percentage" {...props}></Icon>
