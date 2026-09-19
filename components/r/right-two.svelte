<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg8ugcbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sg8ugcbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:right-two" {...props}></Icon>
