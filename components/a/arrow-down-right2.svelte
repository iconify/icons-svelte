<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkwc33ays.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gkwc33ays"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-down-right2" {...props}></Icon>
