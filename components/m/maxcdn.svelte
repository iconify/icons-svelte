<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r313nlbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":24};
const content = `<path class="r313nlbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:maxcdn" {...props}></Icon>
