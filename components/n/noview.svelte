<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaxad1bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eaxad1bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:noview" {...props}></Icon>
