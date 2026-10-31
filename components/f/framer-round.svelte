<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3p3azjzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3p3azjzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:framer-round" {...props}></Icon>
