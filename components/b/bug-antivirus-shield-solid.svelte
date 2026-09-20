<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoebdpbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uoebdpbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-antivirus-shield-solid" {...props}></Icon>
