<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eezel15us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eezel15us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:controls-skipback" {...props}></Icon>
