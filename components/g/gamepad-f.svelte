<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3bww6big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-4};
const content = `<path class="y3bww6big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:gamepad-f" {...props}></Icon>
