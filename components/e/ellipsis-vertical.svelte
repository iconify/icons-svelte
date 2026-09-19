<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol7chu8pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ol7chu8pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:ellipsis-vertical" {...props}></Icon>
