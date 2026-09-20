<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oot8nnbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oot8nnbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:paint-brush" {...props}></Icon>
