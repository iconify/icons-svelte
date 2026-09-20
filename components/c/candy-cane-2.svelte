<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg029z55y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tg029z55y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:candy-cane-2" {...props}></Icon>
