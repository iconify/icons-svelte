<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsiur-b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jsiur-b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:passing" {...props}></Icon>
