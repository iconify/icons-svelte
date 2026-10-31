<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fodpyfbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fodpyfbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-minus-fill-round" {...props}></Icon>
