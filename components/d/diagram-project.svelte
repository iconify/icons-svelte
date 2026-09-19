<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8dp7db7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="r8dp7db7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:diagram-project" {...props}></Icon>
