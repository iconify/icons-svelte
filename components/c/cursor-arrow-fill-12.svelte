<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdwspjbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wdwspjbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cursor-arrow-fill-12" {...props}></Icon>
