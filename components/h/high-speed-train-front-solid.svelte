<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv5n45bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fv5n45bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:high-speed-train-front-solid" {...props}></Icon>
