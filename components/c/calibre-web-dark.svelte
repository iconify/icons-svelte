<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osb188k-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="osb188k-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calibre-web-dark" {...props}></Icon>
