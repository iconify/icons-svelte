<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoc9a1biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoc9a1biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gldotinet" {...props}></Icon>
