<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do713mb7p.css';
import '../../css/w/wft5owbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="do713mb7p"/><path class="wft5owbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:frustrated2" {...props}></Icon>
