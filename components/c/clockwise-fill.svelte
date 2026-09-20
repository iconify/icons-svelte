<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py0818beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py0818beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:clockwise-fill" {...props}></Icon>
