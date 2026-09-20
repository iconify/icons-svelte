<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbxsy4b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qbxsy4b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bottle-and-wine-glass" {...props}></Icon>
