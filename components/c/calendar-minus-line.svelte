<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j089isygs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j089isygs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-minus-line" {...props}></Icon>
