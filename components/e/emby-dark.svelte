<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayp9c8duo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ayp9c8duo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emby-dark" {...props}></Icon>
