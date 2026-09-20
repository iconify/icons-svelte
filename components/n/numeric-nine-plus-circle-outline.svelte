<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfoqfbcpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfoqfbcpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-nine-plus-circle-outline" {...props}></Icon>
