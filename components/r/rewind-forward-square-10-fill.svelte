<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt2orlbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt2orlbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-square-10-fill" {...props}></Icon>
