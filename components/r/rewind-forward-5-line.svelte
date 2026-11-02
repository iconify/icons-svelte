<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q93jv3itp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q93jv3itp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-5-line" {...props}></Icon>
