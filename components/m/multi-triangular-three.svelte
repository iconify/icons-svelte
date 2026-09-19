<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wriglbctt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wriglbctt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:multi-triangular-three" {...props}></Icon>
