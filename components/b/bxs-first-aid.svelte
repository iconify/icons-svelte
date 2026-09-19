<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v688eqkfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v688eqkfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-first-aid" {...props}></Icon>
