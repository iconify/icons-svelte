<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f67na1b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f67na1b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensearch-dark" {...props}></Icon>
