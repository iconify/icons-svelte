<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb7kxrpge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb7kxrpge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bean-off-line" {...props}></Icon>
