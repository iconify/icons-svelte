<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjnqghfek.css';
import '../../css/a/azukwebbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tjnqghfek"/><path class="azukwebbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nintendo" {...props}></Icon>
