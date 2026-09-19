<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ice-5lmvf.css';
import '../../css/o/oafign_da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ice-5lmvf"/><path class="oafign_da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pizza" {...props}></Icon>
