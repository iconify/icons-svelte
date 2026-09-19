<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idqw4tajm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idqw4tajm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu-06" {...props}></Icon>
