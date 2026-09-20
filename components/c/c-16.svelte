<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avrw6g-oj.css';
import '../../css/u/udo50kb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="avrw6g-oj"/><path class="udo50kb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:c-16" {...props}></Icon>
