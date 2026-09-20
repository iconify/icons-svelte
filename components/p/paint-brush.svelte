<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-u7i6rxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-u7i6rxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:paint-brush" {...props}></Icon>
