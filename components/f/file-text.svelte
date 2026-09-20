<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncgybacjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncgybacjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-text" {...props}></Icon>
