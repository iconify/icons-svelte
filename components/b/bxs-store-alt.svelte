<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5ca25bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5ca25bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-store-alt" {...props}></Icon>
