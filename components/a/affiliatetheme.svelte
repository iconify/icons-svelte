<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7hu51muq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r7hu51muq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:affiliatetheme" {...props}></Icon>
