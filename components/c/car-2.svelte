<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u29ffvbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u29ffvbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:car-2" {...props}></Icon>
