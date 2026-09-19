<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id79s1bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="id79s1bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:flag" {...props}></Icon>
