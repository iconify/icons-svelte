<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy05w96zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy05w96zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:garuda-linux" {...props}></Icon>
