<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgejtq3gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgejtq3gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:magisk" {...props}></Icon>
