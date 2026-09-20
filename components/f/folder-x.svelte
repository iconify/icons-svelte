<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkxleq_0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkxleq_0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-x" {...props}></Icon>
