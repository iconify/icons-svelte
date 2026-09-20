<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxqykvbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxqykvbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-hide-outline" {...props}></Icon>
