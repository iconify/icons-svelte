<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dad1ecbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dad1ecbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laptop-2-line" {...props}></Icon>
