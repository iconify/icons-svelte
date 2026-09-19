<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fssbm7fvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":402,"height":512};
const content = `<path class="fssbm7fvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:readthedocs" {...props}></Icon>
