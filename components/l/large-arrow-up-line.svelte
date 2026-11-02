<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-qxeb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-qxeb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-up-line" {...props}></Icon>
