<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol24cq_hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol24cq_hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-line-sharp" {...props}></Icon>
