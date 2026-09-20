<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4mpeygnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4mpeygnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:flip-vertical-square-1" {...props}></Icon>
