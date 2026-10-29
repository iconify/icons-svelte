<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-pzc6fpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-pzc6fpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark-plus-solid" {...props}></Icon>
