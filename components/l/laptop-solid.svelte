<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay164zbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ay164zbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:laptop-solid" {...props}></Icon>
