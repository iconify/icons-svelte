<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu50btbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu50btbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:magnet-gloss" {...props}></Icon>
