<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkhlsmt2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkhlsmt2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-video" {...props}></Icon>
