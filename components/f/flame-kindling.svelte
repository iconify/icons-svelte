<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/punl4aceo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="punl4aceo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flame-kindling" {...props}></Icon>
