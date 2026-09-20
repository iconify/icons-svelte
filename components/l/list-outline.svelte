<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbow88und.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hbow88und"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:list-outline" {...props}></Icon>
