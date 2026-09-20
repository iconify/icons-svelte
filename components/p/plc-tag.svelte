<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u643a_fwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u643a_fwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plc-tag" {...props}></Icon>
