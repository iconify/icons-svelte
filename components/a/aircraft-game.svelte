<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgfi7sblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgfi7sblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:aircraft-game" {...props}></Icon>
