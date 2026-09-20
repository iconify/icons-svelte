<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzdhmac2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzdhmac2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-square-text" {...props}></Icon>
