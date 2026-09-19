<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcc25bptl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcc25bptl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:brightness" {...props}></Icon>
