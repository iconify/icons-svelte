<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bedwffrnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bedwffrnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bunker-silo" {...props}></Icon>
