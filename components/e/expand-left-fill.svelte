<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf1epnbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf1epnbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-left-fill" {...props}></Icon>
