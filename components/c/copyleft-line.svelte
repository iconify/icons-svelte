<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxo6sslyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxo6sslyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copyleft-line" {...props}></Icon>
