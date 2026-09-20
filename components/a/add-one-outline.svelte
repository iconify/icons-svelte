<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz4-e3b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oz4-e3b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:add-one-outline" {...props}></Icon>
