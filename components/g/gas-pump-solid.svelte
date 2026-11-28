<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw899db7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw899db7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gas-pump-solid" {...props}></Icon>
