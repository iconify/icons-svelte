<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huraec29d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huraec29d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:land-plot" {...props}></Icon>
