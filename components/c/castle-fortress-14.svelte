<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kof4q9x0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kof4q9x0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:castle-fortress-14" {...props}></Icon>
