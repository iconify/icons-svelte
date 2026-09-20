<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da-7wgrhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da-7wgrhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-align-middle" {...props}></Icon>
