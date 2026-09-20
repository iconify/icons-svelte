<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q93tdvpzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q93tdvpzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:collapse" {...props}></Icon>
