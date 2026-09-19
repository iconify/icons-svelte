<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5r1m1pkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5r1m1pkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:archive-out" {...props}></Icon>
