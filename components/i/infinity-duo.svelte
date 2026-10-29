<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfc8nsb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfc8nsb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:infinity-duo" {...props}></Icon>
