<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl16xx4ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl16xx4ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-rotate-landscape" {...props}></Icon>
