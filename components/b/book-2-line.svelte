<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hchn5jvhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hchn5jvhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-2-line" {...props}></Icon>
