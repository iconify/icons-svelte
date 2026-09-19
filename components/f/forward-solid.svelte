<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfn07p5qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfn07p5qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:forward-solid" {...props}></Icon>
