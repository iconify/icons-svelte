<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjdzetbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mjdzetbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:one-finger-hold-solid" {...props}></Icon>
