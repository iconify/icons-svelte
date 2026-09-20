<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kffec9iaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kffec9iaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circle-outline" {...props}></Icon>
