<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xysgi34gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xysgi34gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:roman-numeral-6" {...props}></Icon>
