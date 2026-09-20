<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us_qw2b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="us_qw2b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:column-line-outline" {...props}></Icon>
