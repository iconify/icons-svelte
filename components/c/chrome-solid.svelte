<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-z0-pb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-z0-pb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chrome-solid" {...props}></Icon>
