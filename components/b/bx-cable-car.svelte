<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe2og95fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe2og95fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cable-car" {...props}></Icon>
