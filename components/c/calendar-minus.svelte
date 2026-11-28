<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao0h70_1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao0h70_1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-minus" {...props}></Icon>
