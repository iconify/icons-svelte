<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdi64yb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-4};
const content = `<path class="gdi64yb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:gamepad" {...props}></Icon>
