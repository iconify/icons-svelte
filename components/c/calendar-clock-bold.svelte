<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o29_ehb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o29_ehb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-clock-bold" {...props}></Icon>
