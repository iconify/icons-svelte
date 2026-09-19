<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pavwy8ped.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pavwy8ped"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:calendar" {...props}></Icon>
