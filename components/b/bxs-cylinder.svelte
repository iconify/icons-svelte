<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpmawqqcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpmawqqcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cylinder" {...props}></Icon>
