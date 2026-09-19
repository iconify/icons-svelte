<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lidfixb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lidfixb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dune-hd" {...props}></Icon>
