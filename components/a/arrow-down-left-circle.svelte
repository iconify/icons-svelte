<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8oh3cbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g8oh3cbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-left-circle" {...props}></Icon>
