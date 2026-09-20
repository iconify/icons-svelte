<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aobgxb2pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aobgxb2pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:calendar-jump-to-date-remix" {...props}></Icon>
