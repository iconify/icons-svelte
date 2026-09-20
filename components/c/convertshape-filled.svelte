<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa31wen-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa31wen-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:convertshape-filled" {...props}></Icon>
