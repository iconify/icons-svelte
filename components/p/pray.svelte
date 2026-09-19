<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfw-isbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cfw-isbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pray" {...props}></Icon>
