<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlp8g_b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlp8g_b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:list-active" {...props}></Icon>
