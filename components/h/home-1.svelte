<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuht4h08l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuht4h08l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:home-1" {...props}></Icon>
