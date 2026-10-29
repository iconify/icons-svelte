<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7qg_wqtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7qg_wqtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pound-sterling-solid" {...props}></Icon>
