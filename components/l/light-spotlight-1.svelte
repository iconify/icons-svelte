<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hajiifygo.css';
import '../../css/a/a185onbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hajiifygo"/><path class="a185onbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:light-spotlight-1" {...props}></Icon>
