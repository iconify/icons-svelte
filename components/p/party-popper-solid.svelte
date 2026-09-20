<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-_75wncl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c-_75wncl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:party-popper-solid" {...props}></Icon>
