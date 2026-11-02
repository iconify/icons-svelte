<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_0kplbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_0kplbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-minus-2-fill" {...props}></Icon>
