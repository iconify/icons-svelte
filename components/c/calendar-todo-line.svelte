<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7c5r0k6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7c5r0k6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:calendar-todo-line" {...props}></Icon>
