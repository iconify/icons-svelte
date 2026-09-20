<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drgj1zbmh.css';
import '../../css/u/u4xg-pbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="drgj1zbmh"/><path class="u4xg-pbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bulb3" {...props}></Icon>
