<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_3k-myyj.css';
import '../../css/i/i1nctz7rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_3k-myyj"/><path class="i1nctz7rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:pie-chart-1" {...props}></Icon>
