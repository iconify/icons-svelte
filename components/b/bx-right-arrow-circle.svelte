<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktjwxgw4q.css';
import '../../css/o/oyj3-46ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktjwxgw4q"/><path class="oyj3-46ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-right-arrow-circle" {...props}></Icon>
