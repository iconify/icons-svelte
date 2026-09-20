<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amx09ccet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amx09ccet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:replay-30-fill" {...props}></Icon>
