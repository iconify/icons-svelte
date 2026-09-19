<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj_94xbsg.css';
import '../../css/o/o_kremszb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj_94xbsg"/><path class="o_kremszb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:backpack-star" {...props}></Icon>
