<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0v3hv2qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x0v3hv2qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:music-equalizer-remix" {...props}></Icon>
