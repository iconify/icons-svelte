<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfrlmxrjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xfrlmxrjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dangerous-zone-sign-solid" {...props}></Icon>
