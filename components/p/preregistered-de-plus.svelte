<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iumbfubqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iumbfubqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:preregistered-de-plus" {...props}></Icon>
