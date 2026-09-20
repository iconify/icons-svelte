<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxt9wpbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rxt9wpbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:at-t" {...props}></Icon>
