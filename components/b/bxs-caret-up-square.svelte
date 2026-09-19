<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdrc77bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdrc77bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-caret-up-square" {...props}></Icon>
