<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8z640bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8z640bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-bulk-round" {...props}></Icon>
