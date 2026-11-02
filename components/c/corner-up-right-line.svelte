<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id_vwwy8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id_vwwy8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-up-right-line" {...props}></Icon>
