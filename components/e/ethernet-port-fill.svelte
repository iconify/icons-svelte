<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4st_xys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec4st_xys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ethernet-port-fill" {...props}></Icon>
