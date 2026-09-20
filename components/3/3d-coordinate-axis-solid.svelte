<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf4ef19gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lf4ef19gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:3d-coordinate-axis-solid" {...props}></Icon>
