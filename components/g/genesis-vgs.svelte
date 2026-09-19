<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf_i46_pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf_i46_pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:genesis-vgs" {...props}></Icon>
