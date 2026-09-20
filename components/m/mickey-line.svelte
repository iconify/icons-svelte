<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv2ilbbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv2ilbbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mickey-line" {...props}></Icon>
