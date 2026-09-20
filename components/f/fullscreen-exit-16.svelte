<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4yp4jbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q4yp4jbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:fullscreen-exit-16" {...props}></Icon>
