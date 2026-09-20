<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv95rv00s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dv95rv00s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:grid-solid" {...props}></Icon>
