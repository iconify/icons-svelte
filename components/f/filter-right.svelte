<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iok19yqca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iok19yqca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filter-right" {...props}></Icon>
