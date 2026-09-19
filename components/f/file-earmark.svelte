<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srk0lxbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="srk0lxbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark" {...props}></Icon>
