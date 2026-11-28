<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em_6a-_yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em_6a-_yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:noodles-heart" {...props}></Icon>
