<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nycbm_h2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nycbm_h2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:angle-double-left" {...props}></Icon>
