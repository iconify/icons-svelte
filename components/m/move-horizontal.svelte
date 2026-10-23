<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckhmp3bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckhmp3bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:move-horizontal" {...props}></Icon>
