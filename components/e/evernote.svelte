<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veqsyyb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":440};
const content = `<path class="veqsyyb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:evernote" {...props}></Icon>
