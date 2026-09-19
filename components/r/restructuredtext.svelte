<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/garwd4hif.css';
import '../../css/d/d0gmrybii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="garwd4hif"/><path class="d0gmrybii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:restructuredtext" {...props}></Icon>
