<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwibdw4bb.css';
import '../../css/x/xctlkhhlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="xctlkhhlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dots-horizontal-rounded-circle" {...props}></Icon>
