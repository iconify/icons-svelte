<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxqjbcfcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxqjbcfcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fastgate" {...props}></Icon>
