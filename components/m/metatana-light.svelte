<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2blipbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t2blipbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metatana-light" {...props}></Icon>
