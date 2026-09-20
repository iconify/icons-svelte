<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yno2t3b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yno2t3b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:minetest" {...props}></Icon>
