<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkxoldbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dkxoldbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:management-outline" {...props}></Icon>
