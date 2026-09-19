<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoop8ibeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoop8ibeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cube" {...props}></Icon>
