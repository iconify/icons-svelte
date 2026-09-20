<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bud3f4goj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="bud3f4goj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-zip" {...props}></Icon>
