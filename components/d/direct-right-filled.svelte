<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3-xsrb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3-xsrb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:direct-right-filled" {...props}></Icon>
