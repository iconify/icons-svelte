<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym1bg-bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ym1bg-bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bong" {...props}></Icon>
