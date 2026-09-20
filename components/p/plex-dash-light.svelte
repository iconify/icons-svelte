<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5z6um0tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t5z6um0tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex-dash-light" {...props}></Icon>
