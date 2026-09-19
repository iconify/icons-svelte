<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaiw91bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="eaiw91bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:calendar-plus" {...props}></Icon>
