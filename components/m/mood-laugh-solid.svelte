<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jumlimbfi.css';
import '../../css/j/jcs69s1gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jumlimbfi"/><path clip-rule="evenodd" class="jcs69s1gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-laugh-solid" {...props}></Icon>
