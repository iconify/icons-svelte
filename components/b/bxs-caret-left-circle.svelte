<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk0ow5b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk0ow5b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-caret-left-circle" {...props}></Icon>
