<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1a1qsunh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1a1qsunh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hourglass" {...props}></Icon>
