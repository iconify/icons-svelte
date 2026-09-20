<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmlydmupt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hmlydmupt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:accent-light" {...props}></Icon>
