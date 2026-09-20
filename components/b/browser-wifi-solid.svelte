<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agdb4mbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="agdb4mbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-wifi-solid" {...props}></Icon>
