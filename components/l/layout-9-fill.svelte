<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g057fib1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g057fib1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-9-fill" {...props}></Icon>
