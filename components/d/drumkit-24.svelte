<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2k757bsm.css';
import '../../css/p/p3xr9ebyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2k757bsm"/><path clip-rule="evenodd" class="p3xr9ebyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:drumkit-24" {...props}></Icon>
