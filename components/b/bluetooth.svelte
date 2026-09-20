<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghqin2bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghqin2bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:bluetooth" {...props}></Icon>
