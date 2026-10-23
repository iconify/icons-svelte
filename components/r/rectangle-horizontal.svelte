<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc391nbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc391nbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:rectangle-horizontal" {...props}></Icon>
