<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alx5mewnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alx5mewnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cactus-heart" {...props}></Icon>
