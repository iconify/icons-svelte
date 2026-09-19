<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud9xtmhvv.css';
import '../../css/m/mxpx1okuh.css';
import '../../css/w/w_fsjlwse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ud9xtmhvv"/><path class="mxpx1okuh"/><path class="w_fsjlwse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:aok" {...props}></Icon>
