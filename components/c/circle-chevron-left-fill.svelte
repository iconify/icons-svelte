<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqayykb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqayykb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-chevron-left-fill" {...props}></Icon>
