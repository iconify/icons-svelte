<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlsqfxx1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlsqfxx1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-code-plus" {...props}></Icon>
