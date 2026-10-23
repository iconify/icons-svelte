<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyi59vbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyi59vbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-chevrons-left" {...props}></Icon>
