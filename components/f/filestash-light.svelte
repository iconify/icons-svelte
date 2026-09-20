<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5mk3kbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5mk3kbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filestash-light" {...props}></Icon>
