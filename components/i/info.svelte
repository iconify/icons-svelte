<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s241fub9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s241fub9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:info" {...props}></Icon>
