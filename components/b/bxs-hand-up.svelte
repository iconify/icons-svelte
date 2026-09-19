<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd88nzbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd88nzbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hand-up" {...props}></Icon>
