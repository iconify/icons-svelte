<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhozzjajf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhozzjajf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-pointer-left-sharp" {...props}></Icon>
