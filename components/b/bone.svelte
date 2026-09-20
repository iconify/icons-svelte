<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4o6m2bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a4o6m2bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bone" {...props}></Icon>
