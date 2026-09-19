<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z80-l5b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z80-l5b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:airplane-engines-fill" {...props}></Icon>
