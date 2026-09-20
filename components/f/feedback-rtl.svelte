<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2dngh0fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j2dngh0fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:feedback-rtl" {...props}></Icon>
