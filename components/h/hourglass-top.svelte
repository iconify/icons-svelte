<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h20g5bcub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h20g5bcub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hourglass-top" {...props}></Icon>
