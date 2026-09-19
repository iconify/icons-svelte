<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqar3gbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="aqar3gbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:multiline-stroke-12" {...props}></Icon>
