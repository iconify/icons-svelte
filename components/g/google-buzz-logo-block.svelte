<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv3r98bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv3r98bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-buzz-logo-block" {...props}></Icon>
