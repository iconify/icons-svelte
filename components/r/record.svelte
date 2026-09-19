<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9bs2gbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k9bs2gbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:record" {...props}></Icon>
