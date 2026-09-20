<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgmfl_7bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgmfl_7bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:battery-2" {...props}></Icon>
