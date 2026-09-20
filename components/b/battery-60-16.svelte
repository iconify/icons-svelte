<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6c2rnb4s.css';
import '../../css/f/ffaginb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k6c2rnb4s"/><path clip-rule="evenodd" class="ffaginb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:battery-60-16" {...props}></Icon>
