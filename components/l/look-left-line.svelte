<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6xll9b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6xll9b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-left-line" {...props}></Icon>
