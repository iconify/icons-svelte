<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihb7gccby.css';
import '../../css/z/zau8vgbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihb7gccby"/><path class="zau8vgbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:power-supply-plug" {...props}></Icon>
