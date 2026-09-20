<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2cvh0bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2cvh0bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:direct-current" {...props}></Icon>
