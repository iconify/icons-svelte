<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f971rbbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f971rbbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ancient-pavilion-line" {...props}></Icon>
