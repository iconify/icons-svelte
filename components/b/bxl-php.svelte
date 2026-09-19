<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq235rbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq235rbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-php" {...props}></Icon>
