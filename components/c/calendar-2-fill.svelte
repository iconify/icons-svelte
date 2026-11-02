<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftebc-b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftebc-b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-2-fill" {...props}></Icon>
