<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0gvryblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0gvryblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-rightbar-close-fill" {...props}></Icon>
