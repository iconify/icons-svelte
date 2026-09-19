<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa24fvbdv.css';
import '../../css/f/fd7vi_cbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xa24fvbdv"/><path class="fd7vi_cbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-browsers-outline" {...props}></Icon>
