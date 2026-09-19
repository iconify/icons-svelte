<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/patyb2g3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="patyb2g3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:animation-bounce-filled" {...props}></Icon>
