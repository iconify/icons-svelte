<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2nef2b2z.css';
import '../../css/f/fru8l0jpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k2nef2b2z"/><path class="fru8l0jpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-inbox" {...props}></Icon>
