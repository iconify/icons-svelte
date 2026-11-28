<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfhbzf_nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfhbzf_nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:copyleft-solid" {...props}></Icon>
