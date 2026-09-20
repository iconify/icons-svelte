<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4yp20btu.css';
import '../../css/t/tqz5znvkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="m4yp20btu"/><path class="tqz5znvkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:brown-heart" {...props}></Icon>
