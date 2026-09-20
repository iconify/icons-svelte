<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb2tv0bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb2tv0bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-7-1" {...props}></Icon>
