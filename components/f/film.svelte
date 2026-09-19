<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1n6s1bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w1n6s1bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:film" {...props}></Icon>
