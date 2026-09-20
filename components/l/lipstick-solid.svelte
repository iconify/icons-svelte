<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsjl_jbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zsjl_jbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lipstick-solid" {...props}></Icon>
