<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e60rjxbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e60rjxbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:paddlepaddle" {...props}></Icon>
