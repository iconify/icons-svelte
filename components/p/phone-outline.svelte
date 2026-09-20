<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okh3m0bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="okh3m0bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:phone-outline" {...props}></Icon>
