<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpy5x2bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpy5x2bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fingerprint-fill" {...props}></Icon>
