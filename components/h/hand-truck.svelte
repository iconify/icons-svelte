<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0v10vboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0v10vboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hand-truck" {...props}></Icon>
