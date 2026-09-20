<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne1b9cdgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ne1b9cdgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:fitness-center-11" {...props}></Icon>
