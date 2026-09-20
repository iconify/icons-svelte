<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy7n7d1lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy7n7d1lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drinks-2-line" {...props}></Icon>
