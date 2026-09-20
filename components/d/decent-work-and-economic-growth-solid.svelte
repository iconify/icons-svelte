<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lat4ssqys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lat4ssqys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:decent-work-and-economic-growth-solid" {...props}></Icon>
