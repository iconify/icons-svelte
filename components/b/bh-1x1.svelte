<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il691tbvq.css';
import '../../css/u/utka4rg2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="il691tbvq"/><path class="utka4rg2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bh-1x1" {...props}></Icon>
