<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjjeidcdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjjeidcdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clockwise-line" {...props}></Icon>
