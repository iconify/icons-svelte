<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-17fib3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l-17fib3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:code-monitor-1-remix" {...props}></Icon>
