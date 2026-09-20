<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4t3ysxce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4t3ysxce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-vertical-2-fill" {...props}></Icon>
