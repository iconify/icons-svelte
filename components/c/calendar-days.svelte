<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xml7hobsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xml7hobsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-days" {...props}></Icon>
