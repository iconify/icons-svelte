<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppz3qjfbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppz3qjfbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:quote-text-inline" {...props}></Icon>
