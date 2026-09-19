<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu0xh0b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu0xh0b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-plus-filled" {...props}></Icon>
