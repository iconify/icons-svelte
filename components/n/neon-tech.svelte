<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba4wh6eoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba4wh6eoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:neon-tech" {...props}></Icon>
