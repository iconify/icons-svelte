<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8ab5ac2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f8ab5ac2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:magnet" {...props}></Icon>
