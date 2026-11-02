<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_ix5ia0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ix5ia0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-x-2-fill" {...props}></Icon>
