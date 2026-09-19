<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6ik5tbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w6ik5tbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:broadcast-pin" {...props}></Icon>
