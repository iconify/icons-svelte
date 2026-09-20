<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tecp77bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tecp77bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:robinson-light" {...props}></Icon>
