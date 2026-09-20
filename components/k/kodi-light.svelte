<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au9d8ib7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="au9d8ib7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kodi-light" {...props}></Icon>
