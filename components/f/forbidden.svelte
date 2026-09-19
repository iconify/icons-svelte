<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hveltnb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="hveltnb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:forbidden" {...props}></Icon>
