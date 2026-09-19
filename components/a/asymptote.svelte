<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rznww9boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rznww9boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:asymptote" {...props}></Icon>
