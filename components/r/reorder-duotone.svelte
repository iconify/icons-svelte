<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acdl97b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acdl97b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:reorder-duotone" {...props}></Icon>
