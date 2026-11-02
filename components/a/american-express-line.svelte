<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifp5jlboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifp5jlboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:american-express-line" {...props}></Icon>
