<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh6vtxr6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vh6vtxr6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone-paused-solid" {...props}></Icon>
