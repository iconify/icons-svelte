<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw0fkmb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw0fkmb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fahrenheit-line" {...props}></Icon>
