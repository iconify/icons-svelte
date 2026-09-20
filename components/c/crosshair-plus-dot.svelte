<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y04p36b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y04p36b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:crosshair-plus-dot" {...props}></Icon>
