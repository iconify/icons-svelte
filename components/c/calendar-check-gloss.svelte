<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8lmjbcfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8lmjbcfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-check-gloss" {...props}></Icon>
