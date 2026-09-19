<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6ktg6bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6ktg6bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:offline" {...props}></Icon>
