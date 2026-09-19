<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf0y-xe-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf0y-xe-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-alt-filled" {...props}></Icon>
