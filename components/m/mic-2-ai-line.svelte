<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3___g9xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3___g9xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mic-2-ai-line" {...props}></Icon>
