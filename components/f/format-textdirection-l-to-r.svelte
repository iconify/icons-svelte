<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlvk1-bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlvk1-bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-textdirection-l-to-r" {...props}></Icon>
