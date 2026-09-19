<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htms3obeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htms3obeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:framer" {...props}></Icon>
