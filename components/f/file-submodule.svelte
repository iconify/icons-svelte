<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uphm3xb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="uphm3xb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-submodule" {...props}></Icon>
