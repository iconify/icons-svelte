<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_w699bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_w699bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play-skip-back-sharp" {...props}></Icon>
