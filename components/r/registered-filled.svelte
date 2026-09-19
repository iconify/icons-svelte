<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy03h6b4p.css';
import '../../css/b/bqc5p2b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy03h6b4p"/><path class="bqc5p2b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:registered-filled" {...props}></Icon>
