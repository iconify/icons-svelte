<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wamyv4bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wamyv4bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ink-filled" {...props}></Icon>
