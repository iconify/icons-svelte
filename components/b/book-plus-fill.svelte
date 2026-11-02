<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g03waw7_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g03waw7_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-plus-fill" {...props}></Icon>
