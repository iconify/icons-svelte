<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9ocxknif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l9ocxknif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-counterclockwise-16-solid" {...props}></Icon>
