<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i49v73y4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i49v73y4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mobile-phone-camera-remix" {...props}></Icon>
