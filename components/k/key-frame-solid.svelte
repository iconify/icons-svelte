<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm98stbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zm98stbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:key-frame-solid" {...props}></Icon>
