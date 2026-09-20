<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r86_r3bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r86_r3bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-pi-divide-2" {...props}></Icon>
