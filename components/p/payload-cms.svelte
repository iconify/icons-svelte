<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyn2r2b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyn2r2b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:payload-cms" {...props}></Icon>
