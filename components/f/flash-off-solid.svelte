<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxxpfe0-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cxxpfe0-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flash-off-solid" {...props}></Icon>
