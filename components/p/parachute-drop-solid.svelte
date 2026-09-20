<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-emmwbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w-emmwbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:parachute-drop-solid" {...props}></Icon>
