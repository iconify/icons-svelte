<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uch3cth2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uch3cth2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kostos-dark" {...props}></Icon>
