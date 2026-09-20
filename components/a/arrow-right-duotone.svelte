<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpuf93gxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpuf93gxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-right-duotone" {...props}></Icon>
