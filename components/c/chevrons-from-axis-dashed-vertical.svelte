<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsf3-rhca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsf3-rhca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-from-axis-dashed-vertical" {...props}></Icon>
