<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyh6fubpy.css';
import '../../css/x/xmpj6ybey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyh6fubpy"/><path class="xmpj6ybey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:close" {...props}></Icon>
