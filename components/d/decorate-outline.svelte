<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuz046bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nuz046bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:decorate-outline" {...props}></Icon>
