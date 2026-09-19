<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn2auyb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sn2auyb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-90deg-right" {...props}></Icon>
