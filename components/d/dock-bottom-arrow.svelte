<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut3-glbdq.css';
import '../../css/t/tnzkiacoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut3-glbdq"/><path class="tnzkiacoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-bottom-arrow" {...props}></Icon>
