<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-r2a1tbt.css';
import '../../css/x/x3dutabuk.css';
import '../../css/t/t7bcvwf8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="z-r2a1tbt"/><path class="x3dutabuk"/><path class="t7bcvwf8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:collision" {...props}></Icon>
