<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3t03_b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3t03_b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:math-square" {...props}></Icon>
