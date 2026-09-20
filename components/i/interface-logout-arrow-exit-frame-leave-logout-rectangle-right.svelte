<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wctb7iqlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wctb7iqlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-logout-arrow-exit-frame-leave-logout-rectangle-right" {...props}></Icon>
