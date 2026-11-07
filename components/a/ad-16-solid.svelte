<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3uxvcb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m3uxvcb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:ad-16-solid" {...props}></Icon>
