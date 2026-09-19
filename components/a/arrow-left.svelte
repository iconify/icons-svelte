<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z31n7sf4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1472,"height":1600};
const content = `<path class="z31n7sf4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrow-left" {...props}></Icon>
