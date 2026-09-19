<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydmsz_o0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ydmsz_o0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:handwashing" {...props}></Icon>
