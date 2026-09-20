<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i80g1fkkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i80g1fkkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mkdocs-light" {...props}></Icon>
