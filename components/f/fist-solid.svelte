<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8xfq6idc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c8xfq6idc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fist-solid" {...props}></Icon>
