<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg4x4-miu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4x4-miu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-envelope" {...props}></Icon>
