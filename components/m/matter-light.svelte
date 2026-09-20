<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnt2csakl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tnt2csakl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:matter-light" {...props}></Icon>
