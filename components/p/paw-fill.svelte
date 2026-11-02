<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvf7rqj5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvf7rqj5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paw-fill" {...props}></Icon>
