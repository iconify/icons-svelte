<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exdxmabyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exdxmabyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:keyhole-square-full" {...props}></Icon>
