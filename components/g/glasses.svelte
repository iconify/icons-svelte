<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0o5n9beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s0o5n9beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:glasses" {...props}></Icon>
