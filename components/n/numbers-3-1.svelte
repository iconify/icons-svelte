<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9jmp33sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9jmp33sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-3-1" {...props}></Icon>
