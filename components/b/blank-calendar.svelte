<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfxdvzbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hfxdvzbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:blank-calendar" {...props}></Icon>
