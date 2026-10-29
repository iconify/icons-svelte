<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7zs8cblv.css';
import '../../css/p/p8zognblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7zs8cblv"/><path class="p8zognblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:plus" {...props}></Icon>
