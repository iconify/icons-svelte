<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-05zabgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="p-05zabgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:expand-width" {...props}></Icon>
