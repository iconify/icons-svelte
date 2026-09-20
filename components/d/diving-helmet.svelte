<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5ucwkfly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ucwkfly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:diving-helmet" {...props}></Icon>
