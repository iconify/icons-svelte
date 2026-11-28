<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc2tlw_6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc2tlw_6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:car-front-solid" {...props}></Icon>
