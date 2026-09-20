<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2nnlccyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l2nnlccyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-barrel" {...props}></Icon>
