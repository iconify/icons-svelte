<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff0ox68vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff0ox68vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-cny-circle-line" {...props}></Icon>
