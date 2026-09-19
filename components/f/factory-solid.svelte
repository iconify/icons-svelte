<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu9mk0bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="bu9mk0bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:factory-solid" {...props}></Icon>
