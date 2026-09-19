<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4g7h77_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4g7h77_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bold-square-solid" {...props}></Icon>
