<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f77la58rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f77la58rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cursor-pointer" {...props}></Icon>
