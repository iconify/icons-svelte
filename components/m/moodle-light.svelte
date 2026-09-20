<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gby602bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gby602bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:moodle-light" {...props}></Icon>
