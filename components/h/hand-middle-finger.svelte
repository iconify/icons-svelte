<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgejw_z5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hgejw_z5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand-middle-finger" {...props}></Icon>
