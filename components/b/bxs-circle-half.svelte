<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h451a74tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h451a74tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-circle-half" {...props}></Icon>
