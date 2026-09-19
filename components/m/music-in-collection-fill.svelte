<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyr9g0bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eyr9g0bmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:music-in-collection-fill" {...props}></Icon>
