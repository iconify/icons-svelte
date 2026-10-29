<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx8o3xwus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx8o3xwus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gauge" {...props}></Icon>
