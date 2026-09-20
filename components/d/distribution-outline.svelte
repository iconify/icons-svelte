<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um3320xwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="um3320xwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:distribution-outline" {...props}></Icon>
