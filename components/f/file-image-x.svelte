<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtgzif44e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtgzif44e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-image-x" {...props}></Icon>
