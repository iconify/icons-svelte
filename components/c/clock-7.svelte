<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwibdw4bb.css';
import '../../css/z/zgea3bnvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="zgea3bnvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-7" {...props}></Icon>
