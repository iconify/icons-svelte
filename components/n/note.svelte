<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1lly_myo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s1lly_myo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:note" {...props}></Icon>
