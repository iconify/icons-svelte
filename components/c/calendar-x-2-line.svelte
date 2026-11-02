<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0d0rwa6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0d0rwa6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-x-2-line" {...props}></Icon>
