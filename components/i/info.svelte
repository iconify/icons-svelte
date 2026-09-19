<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0-0whfbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0-0whfbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:info" {...props}></Icon>
