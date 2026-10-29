<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orenhhbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orenhhbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-chevrons-left" {...props}></Icon>
