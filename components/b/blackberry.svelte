<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfolyzbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfolyzbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:blackberry" {...props}></Icon>
