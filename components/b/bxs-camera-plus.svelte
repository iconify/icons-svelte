<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8fgs1blq.css';
import '../../css/t/taswdu53c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8fgs1blq"/><path class="taswdu53c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-camera-plus" {...props}></Icon>
