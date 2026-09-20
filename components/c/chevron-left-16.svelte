<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrayo7mvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wrayo7mvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-left-16" {...props}></Icon>
