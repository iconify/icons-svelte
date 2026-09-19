<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2r8k2b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2r8k2b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:map-pin-solid" {...props}></Icon>
