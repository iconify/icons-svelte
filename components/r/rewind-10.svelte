<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atjum7blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atjum7blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rewind-10" {...props}></Icon>
