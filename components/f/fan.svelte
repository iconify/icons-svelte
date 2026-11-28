<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn5y-x9jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn5y-x9jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fan" {...props}></Icon>
