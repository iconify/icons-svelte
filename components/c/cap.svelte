<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppbz2dbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppbz2dbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cap" {...props}></Icon>
