<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8qp24b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8qp24b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-minus" {...props}></Icon>
