<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcui2o1_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rcui2o1_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:blood-drop-donation-solid" {...props}></Icon>
