<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmo9ppb1i.css';
import '../../css/r/rf6qy1bai.css';
import '../../css/h/hsg9le06j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lmo9ppb1i"><path class="rf6qy1bai"/><path class="hsg9le06j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:diagram-split-horizontal" {...props}></Icon>
