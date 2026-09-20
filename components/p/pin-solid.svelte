<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7ndyqh_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d7ndyqh_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:pin-solid" {...props}></Icon>
