<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzelsrg4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzelsrg4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:eject-filled" {...props}></Icon>
