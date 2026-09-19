<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wayv_wbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wayv_wbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:movie" {...props}></Icon>
