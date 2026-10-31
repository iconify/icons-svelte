<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gghi3zbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gghi3zbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-minus-gloss" {...props}></Icon>
