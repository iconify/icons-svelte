<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm5a0s0xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5a0s0xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:more-vertical-fill-round" {...props}></Icon>
