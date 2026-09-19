<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jit-jvg3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jit-jvg3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-left-06" {...props}></Icon>
