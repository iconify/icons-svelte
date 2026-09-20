<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4qt0-s2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o4qt0-s2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emby-light" {...props}></Icon>
