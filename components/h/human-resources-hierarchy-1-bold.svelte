<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/powdozs3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="powdozs3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:human-resources-hierarchy-1-bold" {...props}></Icon>
