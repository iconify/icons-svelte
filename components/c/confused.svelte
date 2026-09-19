<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn7-6cg6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn7-6cg6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:confused" {...props}></Icon>
