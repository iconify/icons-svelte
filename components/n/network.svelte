<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc1aw7qal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nc1aw7qal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:network" {...props}></Icon>
