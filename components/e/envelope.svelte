<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9g5gkbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9g5gkbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:envelope" {...props}></Icon>
