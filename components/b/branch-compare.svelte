<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3ov37b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c3ov37b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:branch-compare" {...props}></Icon>
