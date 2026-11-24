<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtw_a9i1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtw_a9i1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carets-from-axis-vertical-filled" {...props}></Icon>
