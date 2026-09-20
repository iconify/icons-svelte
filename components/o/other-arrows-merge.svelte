<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohjefuxdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ohjefuxdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-arrows-merge" {...props}></Icon>
