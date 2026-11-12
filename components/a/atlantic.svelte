<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_8lbpb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_8lbpb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:atlantic" {...props}></Icon>
