<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb7-bug3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb7-bug3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bentley" {...props}></Icon>
