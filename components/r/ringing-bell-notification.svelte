<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuhlkkm_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fuhlkkm_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ringing-bell-notification" {...props}></Icon>
