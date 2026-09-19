<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p21ha7b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p21ha7b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:drop-right" {...props}></Icon>
