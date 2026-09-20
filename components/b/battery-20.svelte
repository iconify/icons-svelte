<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_xce6tdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_xce6tdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-20" {...props}></Icon>
