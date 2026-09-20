<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxw3evb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxw3evb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dribbble-line" {...props}></Icon>
