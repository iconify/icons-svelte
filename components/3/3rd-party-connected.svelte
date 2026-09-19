<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5it-si_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g5it-si_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:3rd-party-connected" {...props}></Icon>
