<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e64liw9qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1408};
const content = `<path class="e64liw9qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:filter" {...props}></Icon>
