<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7eeem2yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r7eeem2yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:creative-commons-pd" {...props}></Icon>
