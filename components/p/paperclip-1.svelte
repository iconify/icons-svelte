<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd5brzbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="fd5brzbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:paperclip-1" {...props}></Icon>
