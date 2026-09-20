<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj4b3949s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-6};
const content = `<path class="xj4b3949s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:gamepad-retro" {...props}></Icon>
