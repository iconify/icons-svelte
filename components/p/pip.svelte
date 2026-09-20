<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgts3ebcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fgts3ebcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pip" {...props}></Icon>
