<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyo64f5ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="eyo64f5ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-curvy-both-direction-2-both-direction-arrow-curvy-diagram-zigzag-horizontal" {...props}></Icon>
