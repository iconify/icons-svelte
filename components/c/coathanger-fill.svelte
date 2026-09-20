<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpc4lacel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpc4lacel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coathanger-fill" {...props}></Icon>
