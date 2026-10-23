<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az1a-kbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az1a-kbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map-pin-plus" {...props}></Icon>
