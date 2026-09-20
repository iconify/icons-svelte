<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwuvc_gqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jwuvc_gqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:good-health-and-well-being-solid" {...props}></Icon>
