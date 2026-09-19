<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djqkv3dft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djqkv3dft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chat-circle-check" {...props}></Icon>
