<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc1dn3bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc1dn3bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:left-arrow-circle" {...props}></Icon>
