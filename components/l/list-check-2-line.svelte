<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4kbw18me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4kbw18me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-2-line" {...props}></Icon>
