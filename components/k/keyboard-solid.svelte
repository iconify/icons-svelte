<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgi_gv_ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgi_gv_ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:keyboard-solid" {...props}></Icon>
