<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu0w0hb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fu0w0hb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:bold" {...props}></Icon>
