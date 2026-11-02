<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6gd5e7ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6gd5e7ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mastercard-fill" {...props}></Icon>
