<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2u_1obyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2u_1obyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pipe-valve" {...props}></Icon>
