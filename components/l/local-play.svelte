<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9jr4hbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="a9jr4hbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-play" {...props}></Icon>
