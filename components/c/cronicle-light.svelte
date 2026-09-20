<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ai52npl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s9ai52npl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cronicle-light" {...props}></Icon>
