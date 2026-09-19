<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjq3ac0dg.css';
import '../../css/i/ipjtrphds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjq3ac0dg"/><path class="ipjtrphds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:building" {...props}></Icon>
