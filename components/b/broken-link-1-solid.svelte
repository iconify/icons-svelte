<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmd-mebox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lmd-mebox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:broken-link-1-solid" {...props}></Icon>
