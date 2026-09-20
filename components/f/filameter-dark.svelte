<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo3hfxvig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uo3hfxvig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filameter-dark" {...props}></Icon>
