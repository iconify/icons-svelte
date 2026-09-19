<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5am15b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u5am15b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:globe-europe-africa" {...props}></Icon>
