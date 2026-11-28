<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll1daf0dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll1daf0dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:info" {...props}></Icon>
