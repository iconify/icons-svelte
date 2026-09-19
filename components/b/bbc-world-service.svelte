<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx_s6bg8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx_s6bg8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bbc-world-service" {...props}></Icon>
