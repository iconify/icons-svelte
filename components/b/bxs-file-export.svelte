<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwvda6otg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwvda6otg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-export" {...props}></Icon>
