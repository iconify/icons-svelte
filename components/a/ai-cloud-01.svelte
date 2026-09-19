<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cguul6b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cguul6b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-cloud-01" {...props}></Icon>
