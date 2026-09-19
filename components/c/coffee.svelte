<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w37f9tbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w37f9tbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:coffee" {...props}></Icon>
