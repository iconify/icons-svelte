<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn45mpc_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn45mpc_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:recycling" {...props}></Icon>
