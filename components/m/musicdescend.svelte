<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1ryxkbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m1ryxkbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:musicdescend" {...props}></Icon>
