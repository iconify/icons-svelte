<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0r3kmi5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k0r3kmi5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:ban-solid" {...props}></Icon>
