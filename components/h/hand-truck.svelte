<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsjpldb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsjpldb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hand-truck" {...props}></Icon>
