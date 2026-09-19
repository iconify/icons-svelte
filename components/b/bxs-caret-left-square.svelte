<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7p_eac0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7p_eac0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-caret-left-square" {...props}></Icon>
