<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlr4l2bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1792};
const content = `<path class="vlr4l2bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:neuter" {...props}></Icon>
