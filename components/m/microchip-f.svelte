<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo63qp7ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="xo63qp7ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:microchip-f" {...props}></Icon>
