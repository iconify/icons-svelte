<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2b_f4a6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2b_f4a6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-circle-three-quarter" {...props}></Icon>
