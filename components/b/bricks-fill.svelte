<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx9vchbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx9vchbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bricks-fill" {...props}></Icon>
