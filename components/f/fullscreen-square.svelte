<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmf453b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmf453b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fullscreen-square" {...props}></Icon>
