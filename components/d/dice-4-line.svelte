<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyop4rbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyop4rbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-4-line" {...props}></Icon>
