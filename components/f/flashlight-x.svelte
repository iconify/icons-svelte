<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_zqm_bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_zqm_bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flashlight-x" {...props}></Icon>
