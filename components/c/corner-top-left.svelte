<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb_usvbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb_usvbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:corner-top-left" {...props}></Icon>
