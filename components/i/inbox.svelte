<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puh1-6bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="puh1-6bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:inbox" {...props}></Icon>
