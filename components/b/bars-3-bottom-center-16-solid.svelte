<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_4k9-uiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c_4k9-uiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bars-3-bottom-center-16-solid" {...props}></Icon>
