<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny9k_dr0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ny9k_dr0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:computer-outline" {...props}></Icon>
