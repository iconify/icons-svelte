<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahlbw-byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahlbw-byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:hal" {...props}></Icon>
