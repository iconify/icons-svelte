<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf376njnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gf376njnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nzb-dav-dark" {...props}></Icon>
