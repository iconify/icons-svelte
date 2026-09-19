<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp79jsbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp79jsbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowl-balls" {...props}></Icon>
