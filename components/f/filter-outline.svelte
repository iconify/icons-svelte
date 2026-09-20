<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn2uc9buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hn2uc9buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:filter-outline" {...props}></Icon>
