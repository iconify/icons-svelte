<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7gb4mbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7gb4mbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:flash-solid" {...props}></Icon>
