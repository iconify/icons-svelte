<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yel1-p0dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yel1-p0dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:can-soda" {...props}></Icon>
