<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkea-vjte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rkea-vjte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:car-key" {...props}></Icon>
