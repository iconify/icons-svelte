<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zteszgb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zteszgb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-right-07" {...props}></Icon>
