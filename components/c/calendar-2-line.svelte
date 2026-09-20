<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htxsu-e7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htxsu-e7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-2-line" {...props}></Icon>
