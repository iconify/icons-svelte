<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh70epuyr.css';
import '../../css/v/v4_ncezad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vh70epuyr"/><path class="v4_ncezad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:reminder" {...props}></Icon>
