<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm30bdpol.css';
import '../../css/t/tvbix7bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm30bdpol"/><path class="tvbix7bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-right-stroke-circle-filled" {...props}></Icon>
