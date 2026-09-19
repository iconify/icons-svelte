<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jceo9d0_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jceo9d0_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-week-fill" {...props}></Icon>
