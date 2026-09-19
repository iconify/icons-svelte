<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9vm4ubfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9vm4ubfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-dice-2" {...props}></Icon>
