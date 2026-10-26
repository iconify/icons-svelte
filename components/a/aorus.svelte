<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg5dp-llk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg5dp-llk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aorus" {...props}></Icon>
