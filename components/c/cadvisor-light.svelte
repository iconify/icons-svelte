<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq7p2zb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sq7p2zb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cadvisor-light" {...props}></Icon>
