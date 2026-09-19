<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xowyx0jna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xowyx0jna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-flame" {...props}></Icon>
