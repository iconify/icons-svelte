<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcpoq0b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lcpoq0b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:polygon-solid" {...props}></Icon>
