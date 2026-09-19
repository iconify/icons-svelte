<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0b_s6bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0b_s6bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:approximate" {...props}></Icon>
