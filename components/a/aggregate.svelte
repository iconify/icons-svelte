<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft4l_3bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ft4l_3bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:aggregate" {...props}></Icon>
