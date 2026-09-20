<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f69cxl6mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f69cxl6mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:grid" {...props}></Icon>
