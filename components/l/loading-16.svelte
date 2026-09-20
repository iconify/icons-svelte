<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9jsn7btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k9jsn7btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:loading-16" {...props}></Icon>
