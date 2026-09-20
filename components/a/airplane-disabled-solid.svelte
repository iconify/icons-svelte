<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfcl9ekst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfcl9ekst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:airplane-disabled-solid" {...props}></Icon>
