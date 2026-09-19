<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-u3i328k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-u3i328k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cooling-square" {...props}></Icon>
