<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb-ee9b3j.css';
import '../../css/b/bwcanry2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb-ee9b3j"/><path class="bwcanry2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-left-square" {...props}></Icon>
