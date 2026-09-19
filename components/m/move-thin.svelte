<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtkp4jb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtkp4jb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:move-thin" {...props}></Icon>
