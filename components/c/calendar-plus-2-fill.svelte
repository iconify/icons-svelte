<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t60pv0b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t60pv0b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-plus-2-fill" {...props}></Icon>
